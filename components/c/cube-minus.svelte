<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sceb6cc9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sceb6cc9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cube-minus" {...props}></Icon>
