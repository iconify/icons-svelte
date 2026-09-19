<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fro1igbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fro1igbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-left-down" {...props}></Icon>
