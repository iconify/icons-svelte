<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eof5pzb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="eof5pzb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-left-circle-fill" {...props}></Icon>
