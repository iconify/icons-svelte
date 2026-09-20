<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6cjc0bct.css';
import '../../css/x/xb829869a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v6cjc0bct"/><path class="xb829869a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-terraform" {...props}></Icon>
