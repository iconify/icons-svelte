<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0p5l9byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0p5l9byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:co-op" {...props}></Icon>
