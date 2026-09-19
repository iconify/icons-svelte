<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7r18vb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g7r18vb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:radiowaves-right" {...props}></Icon>
