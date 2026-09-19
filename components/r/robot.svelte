<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fgn4zzbxd.css';
import '../../css/b/b7b6egbjf.css';
import '../../css/n/nvukm8ejr.css';
import '../../css/n/nshm1nb1i.css';
import '../../css/d/dx6zqbcdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fgn4zzbxd"/><path class="b7b6egbjf"/><path class="nvukm8ejr"/><path class="nshm1nb1i"/><path class="dx6zqbcdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:robot" {...props}></Icon>
