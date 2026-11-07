<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2t55rbji.css';
import '../../css/n/nxq0bqbft.css';
import '../../css/d/d99hl0bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2t55rbji"/><path class="nxq0bqbft"/><path class="d99hl0bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-calling-bold" {...props}></Icon>
