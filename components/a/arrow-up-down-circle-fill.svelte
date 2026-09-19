<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfamsoo7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dfamsoo7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-down-circle-fill" {...props}></Icon>
