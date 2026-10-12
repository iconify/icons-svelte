<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoams9w2x.css';
import '../../css/t/tnqh3bc1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uoams9w2x"/><path class="tnqh3bc1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:banknote-20" {...props}></Icon>
