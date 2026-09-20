<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l32lerbfx.css';
import '../../css/v/v-975mjhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="v-975mjhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-lua-open" {...props}></Icon>
