<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/n/n0g6jmbfy.css';
import '../../css/d/d_ofrbb7y.css';
import '../../css/p/pfnt1nf9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="n0g6jmbfy"/><path class="d_ofrbb7y"/><path class="pfnt1nf9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:forklift" {...props}></Icon>
