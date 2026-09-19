<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty51eibwy.css';
import '../../css/x/xi_khzqzd.css';
import '../../css/b/beok1wbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ty51eibwy"/><path class="xi_khzqzd"/><path class="beok1wbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mic-off-outline" {...props}></Icon>
