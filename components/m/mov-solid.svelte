<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbr-kl8vw.css';
import '../../css/j/j7zcxhbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nbr-kl8vw"/><path clip-rule="evenodd" class="j7zcxhbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mov-solid" {...props}></Icon>
