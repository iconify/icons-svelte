<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyi0tcctg.css';
import '../../css/b/bz41hmbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="fyi0tcctg"/><path class="bz41hmbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-drinking-fountain" {...props}></Icon>
