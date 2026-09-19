<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtc0sibbu.css';
import '../../css/a/a05zqoswp.css';
import '../../css/i/indds1b1z.css';
import '../../css/v/v4-oeibyk.css';
import '../../css/z/zv_0hpbfs.css';
import '../../css/t/t92mmzq6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gtc0sibbu"/><path class="a05zqoswp"/><path class="indds1b1z"/><path class="v4-oeibyk"/><path class="zv_0hpbfs"/><path class="t92mmzq6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ledger" {...props}></Icon>
