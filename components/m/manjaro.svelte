<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq6s0bq6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq6s0bq6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:manjaro" {...props}></Icon>
