<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol0qizktf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol0qizktf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed" {...props}></Icon>
