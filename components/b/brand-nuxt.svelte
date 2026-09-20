<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp2s87g9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp2s87g9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-nuxt" {...props}></Icon>
