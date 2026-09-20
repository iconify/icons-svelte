<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqx5vab9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqx5vab9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-zip-fill" {...props}></Icon>
