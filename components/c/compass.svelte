<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3xhoopp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ms3xhoopp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:compass" {...props}></Icon>
