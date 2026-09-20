<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quvo1rd9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quvo1rd9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:grocy" {...props}></Icon>
