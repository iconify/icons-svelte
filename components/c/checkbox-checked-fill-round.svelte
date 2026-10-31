<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq7f3kb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq7f3kb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:checkbox-checked-fill-round" {...props}></Icon>
