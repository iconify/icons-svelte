<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapub4bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qapub4bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:page-remove" {...props}></Icon>
