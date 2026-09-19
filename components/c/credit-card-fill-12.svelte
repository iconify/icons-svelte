<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpjp_6bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kpjp_6bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-fill-12" {...props}></Icon>
