<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h32t530tv.css';
import '../../css/n/n9cednr3v.css';
import '../../css/u/u5jnbt9yj.css';
import '../../css/h/hftaky--n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h32t530tv"/><path class="n9cednr3v"/><path class="u5jnbt9yj"/><path class="hftaky--n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:neutral" {...props}></Icon>
