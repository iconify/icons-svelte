<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5fzb4bue.css';
import '../../css/i/iennupbfk.css';
import '../../css/z/ztja4fb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f5fzb4bue"/><path class="iennupbfk"/><path class="ztja4fb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-cw-48" {...props}></Icon>
