<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj--xhbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sj--xhbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:film-slate-remix" {...props}></Icon>
