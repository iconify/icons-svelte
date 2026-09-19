<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0-20imgh.css';
import '../../css/k/kqs-8dbyr.css';
import '../../css/k/kz7mlmbof.css';
import '../../css/l/lau2l9j4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0-20imgh"/><path class="kqs-8dbyr"/><path class="kz7mlmbof"/><path class="lau2l9j4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:devilhorns" {...props}></Icon>
