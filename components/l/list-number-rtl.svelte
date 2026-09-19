<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejuhadc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ejuhadc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:list-number-rtl" {...props}></Icon>
