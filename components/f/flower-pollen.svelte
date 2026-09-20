<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-5qib8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-5qib8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flower-pollen" {...props}></Icon>
