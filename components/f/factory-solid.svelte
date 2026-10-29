<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kky9d-ehz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kky9d-ehz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:factory-solid" {...props}></Icon>
