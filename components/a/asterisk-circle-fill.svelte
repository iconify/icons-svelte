<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb3cn3bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yb3cn3bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:asterisk-circle-fill" {...props}></Icon>
