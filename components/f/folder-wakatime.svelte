<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs74-mbgw.css';
import '../../css/j/jwv6tpbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xs74-mbgw"/><path class="jwv6tpbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-wakatime" {...props}></Icon>
