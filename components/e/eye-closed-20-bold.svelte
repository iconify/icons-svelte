<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djp6rcbat.css';
import '../../css/n/n292q15ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="djp6rcbat"/><path class="n292q15ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-closed-20-bold" {...props}></Icon>
