<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pghkivbqq.css';
import '../../css/n/n_12w22lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pghkivbqq"/><path class="n_12w22lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:excavator-20" {...props}></Icon>
