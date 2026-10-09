<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ni6vb5b.css';
import '../../css/t/tyv6bwbtz.css';
import '../../css/a/ag5d8ub9y.css';
import '../../css/i/ijbr7jekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="tyv6bwbtz"/><path class="ag5d8ub9y"/><path class="ijbr7jekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lever-20" {...props}></Icon>
