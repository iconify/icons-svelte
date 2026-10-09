<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi1hn-gpe.css';
import '../../css/q/qln6u-bog.css';
import '../../css/n/n02nodbdf.css';
import '../../css/o/okxkqqbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pi1hn-gpe"/><path class="qln6u-bog"/><path class="n02nodbdf"/><path class="okxkqqbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-20-bold" {...props}></Icon>
