<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es41gybou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es41gybou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rewe" {...props}></Icon>
