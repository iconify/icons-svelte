<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei4r2welx.css';
import '../../css/n/nt_i2cb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei4r2welx"/><path class="nt_i2cb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:power" {...props}></Icon>
