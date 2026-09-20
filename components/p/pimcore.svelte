<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1_-qsb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1_-qsb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pimcore" {...props}></Icon>
