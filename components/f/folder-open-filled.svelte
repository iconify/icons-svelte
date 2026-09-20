<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur1o9c2kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur1o9c2kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-open-filled" {...props}></Icon>
