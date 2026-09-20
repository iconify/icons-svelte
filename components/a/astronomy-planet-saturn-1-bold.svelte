<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf2ng0bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf2ng0bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:astronomy-planet-saturn-1-bold" {...props}></Icon>
