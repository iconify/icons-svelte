<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu2_0m1vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bu2_0m1vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:donut-bitten-outline" {...props}></Icon>
