<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_3tzc3zp.css';
import '../../css/s/szf5qrbdc.css';
import '../../css/u/ud4iudbrz.css';
import '../../css/y/y3b9nlbqo.css';
import '../../css/m/m47cu8x2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n_3tzc3zp"/><path class="szf5qrbdc"/><path class="ud4iudbrz"/><path class="y3b9nlbqo"/><path class="m47cu8x2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:novelwriter" {...props}></Icon>
