<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr7aie1zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr7aie1zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:konami" {...props}></Icon>
