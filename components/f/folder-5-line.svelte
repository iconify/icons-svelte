<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiut2o5jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiut2o5jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-5-line" {...props}></Icon>
