<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnboovlfn.css';
import '../../css/c/c-h-kzbwd.css';
import '../../css/g/giut3nb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mnboovlfn"/><path class="c-h-kzbwd"/><path class="giut3nb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-stopwatch" {...props}></Icon>
