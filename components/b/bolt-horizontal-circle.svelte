<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1g8j_m8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="a1g8j_m8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt-horizontal-circle" {...props}></Icon>
