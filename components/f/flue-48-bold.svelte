<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jikxxnb7a.css';
import '../../css/r/r_d_ijm8a.css';
import '../../css/d/d8xz_bcrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jikxxnb7a"/><path class="r_d_ijm8a"/><path class="d8xz_bcrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flue-48-bold" {...props}></Icon>
