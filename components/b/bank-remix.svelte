<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcc280bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mcc280bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bank-remix" {...props}></Icon>
