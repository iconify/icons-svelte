<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpidcbbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="kpidcbbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ror" {...props}></Icon>
