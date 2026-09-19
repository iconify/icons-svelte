<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3b5a86vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="a3b5a86vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:app-badge-fill" {...props}></Icon>
