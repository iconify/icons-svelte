<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anpy_cbsi.css';
import '../../css/l/ljm5ww87o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="anpy_cbsi"/><path class="ljm5ww87o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:graduation-cap-20-bold" {...props}></Icon>
