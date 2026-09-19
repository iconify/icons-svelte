<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfdi55bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jfdi55bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-right-up" {...props}></Icon>
