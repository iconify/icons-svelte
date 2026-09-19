<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh5xrqc4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vh5xrqc4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-circle" {...props}></Icon>
