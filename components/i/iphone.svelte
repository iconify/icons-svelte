<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktvza_ycb.css';
import '../../css/a/ajbc88bet.css';
import '../../css/u/u9db6-ydy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ktvza_ycb"/><path class="ajbc88bet"/><circle class="u9db6-ydy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:iphone" {...props}></Icon>
