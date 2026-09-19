<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzn-3lsgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yzn-3lsgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:greaterthan-square-fill" {...props}></Icon>
