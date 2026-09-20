<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0mztybcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0mztybcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-multiple" {...props}></Icon>
