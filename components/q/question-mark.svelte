<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u73_7tktp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u73_7tktp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:question-mark" {...props}></Icon>
