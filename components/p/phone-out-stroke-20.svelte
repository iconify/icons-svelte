<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrjmnmpml.css';
import '../../css/j/juwohhbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rrjmnmpml"/><path class="juwohhbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-out-stroke-20" {...props}></Icon>
