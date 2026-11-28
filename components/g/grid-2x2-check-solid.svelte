<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv7a538cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv7a538cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-2x2-check-solid" {...props}></Icon>
