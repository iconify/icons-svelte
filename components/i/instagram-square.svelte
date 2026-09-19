<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru5m9utxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ru5m9utxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:instagram-square" {...props}></Icon>
