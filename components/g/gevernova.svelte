<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiqfbpcfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1545,"height":1544};
const content = `<path class="oiqfbpcfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gevernova" {...props}></Icon>
