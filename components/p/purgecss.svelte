<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy9pv4mjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy9pv4mjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:purgecss" {...props}></Icon>
