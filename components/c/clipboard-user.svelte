<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohe_6i2-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohe_6i2-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-user" {...props}></Icon>
