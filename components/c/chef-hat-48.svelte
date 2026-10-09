<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr0p19bkd.css';
import '../../css/z/zfxhzybhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zr0p19bkd"/><path class="zfxhzybhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-hat-48" {...props}></Icon>
