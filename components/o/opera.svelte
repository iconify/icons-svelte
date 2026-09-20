<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa_537b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<path class="oa_537b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:opera" {...props}></Icon>
