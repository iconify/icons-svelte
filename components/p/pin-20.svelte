<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8fvfdcfq.css';
import '../../css/n/n9js5qbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m8fvfdcfq"/><path class="n9js5qbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pin-20" {...props}></Icon>
