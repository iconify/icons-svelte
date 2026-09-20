<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbxkrlbja.css';
import '../../css/a/a7dps37by.css';
import '../../css/u/ubp-y7bxd.css';
import '../../css/z/zbkoumh9m.css';
import '../../css/s/sft5hp-6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbxkrlbja"/><ellipse class="a7dps37by"/><ellipse class="ubp-y7bxd"/><ellipse class="zbkoumh9m"/><ellipse class="sft5hp-6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:argus" {...props}></Icon>
