<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn_w55smn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fn_w55smn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-badge-plus-fill" {...props}></Icon>
