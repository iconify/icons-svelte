<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqx-9g47c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqx-9g47c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:more" {...props}></Icon>
