<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbf1ts0hu.css';
import '../../css/f/fcgr3_agr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rbf1ts0hu"/><path clip-rule="evenodd" class="fcgr3_agr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:money-16" {...props}></Icon>
