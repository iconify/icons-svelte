<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu6i2gb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tu6i2gb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-pp" {...props}></Icon>
