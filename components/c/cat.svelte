<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1sqy38ml.css';
import '../../css/u/u1u-os4ws.css';
import '../../css/b/b0fe4tbca.css';
import '../../css/f/fkadcub_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p1sqy38ml"/><path class="u1u-os4ws"/><path class="b0fe4tbca"/><path class="fkadcub_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cat" {...props}></Icon>
