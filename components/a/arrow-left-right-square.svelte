<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu5-snb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mu5-snb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-left-right-square" {...props}></Icon>
