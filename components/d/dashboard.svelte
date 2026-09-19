<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irnn-u13t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irnn-u13t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dashboard" {...props}></Icon>
