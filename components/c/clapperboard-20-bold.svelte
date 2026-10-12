<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh8z6bbpj.css';
import '../../css/k/kpsumujvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mh8z6bbpj"/><path class="kpsumujvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clapperboard-20-bold" {...props}></Icon>
