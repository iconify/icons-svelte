<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwwxm2b6y.css';
import '../../css/j/j8adrjbzg.css';
import '../../css/k/ken9h11xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwwxm2b6y"/><path class="j8adrjbzg"/><path class="ken9h11xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-wifi" {...props}></Icon>
