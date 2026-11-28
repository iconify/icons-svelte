<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu09rguss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu09rguss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:molecule" {...props}></Icon>
