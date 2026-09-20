<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdt-6nblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdt-6nblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-cent" {...props}></Icon>
