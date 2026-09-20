<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2c-uxbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t2c-uxbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dices-entertainment-gaming-dices-remix" {...props}></Icon>
