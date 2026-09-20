<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqgu7wbdd.css';
import '../../css/f/f7k04-ada.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sqgu7wbdd"/><path clip-rule="evenodd" class="f7k04-ada"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:archive-solid" {...props}></Icon>
