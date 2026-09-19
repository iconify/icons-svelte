<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4te6mbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="q4te6mbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:payoneer" {...props}></Icon>
