<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yow4obkue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yow4obkue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-rubl-circle-fill" {...props}></Icon>
