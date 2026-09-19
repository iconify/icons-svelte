<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeaogk41p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="oeaogk41p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-up-right" {...props}></Icon>
