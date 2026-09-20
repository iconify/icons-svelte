<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9wu50bnx.css';
import '../../css/a/a__ik5b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j9wu50bnx"/><path class="a__ik5b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cisco-anyconnect" {...props}></Icon>
