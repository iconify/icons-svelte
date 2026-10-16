<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saail3bjj.css';
import '../../css/v/v58dvfb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="saail3bjj"/><path class="v58dvfb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:level-gauge-20-bold" {...props}></Icon>
