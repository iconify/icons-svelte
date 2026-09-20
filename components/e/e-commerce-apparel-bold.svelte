<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km7s_km6t.css';
import '../../css/n/nb04b04xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km7s_km6t"/><path class="nb04b04xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:e-commerce-apparel-bold" {...props}></Icon>
