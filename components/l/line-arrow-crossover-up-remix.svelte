<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcryt8kkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tcryt8kkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-crossover-up-remix" {...props}></Icon>
