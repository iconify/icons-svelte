<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co28yzgia.css';
import '../../css/i/i0wzpzqff.css';
import '../../css/t/tifg0imgb.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="co28yzgia"/><path class="i0wzpzqff"/><path class="tifg0imgb"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:package-check-48" {...props}></Icon>
