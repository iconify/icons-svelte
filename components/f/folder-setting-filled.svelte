<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymx794b5s.css';
import '../../css/h/h1_3onb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymx794b5s"/><path class="h1_3onb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-setting-filled" {...props}></Icon>
