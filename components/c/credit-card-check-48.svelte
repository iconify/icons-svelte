<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2sfo7bun.css';
import '../../css/i/i8lgm5omt.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z2sfo7bun"/><path class="i8lgm5omt"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:credit-card-check-48" {...props}></Icon>
