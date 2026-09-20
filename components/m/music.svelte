<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1tms5bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="i1tms5bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:music" {...props}></Icon>
