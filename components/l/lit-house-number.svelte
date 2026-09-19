<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya7p8kszo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya7p8kszo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lit-house-number" {...props}></Icon>
