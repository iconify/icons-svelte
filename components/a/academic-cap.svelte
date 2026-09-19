<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0wfnm_-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0wfnm_-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:academic-cap" {...props}></Icon>
