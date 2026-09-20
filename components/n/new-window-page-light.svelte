<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5f2fnxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw5f2fnxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:new-window-page-light" {...props}></Icon>
