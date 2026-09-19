<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q259b5wfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q259b5wfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:e-bike-1" {...props}></Icon>
