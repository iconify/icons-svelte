<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxn9sbcuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jxn9sbcuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:minus-circle-fill" {...props}></Icon>
