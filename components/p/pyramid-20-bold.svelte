<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig39blqsl.css';
import '../../css/t/tx633bbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ig39blqsl"/><path class="tx633bbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pyramid-20-bold" {...props}></Icon>
