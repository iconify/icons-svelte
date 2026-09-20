<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdqx58tih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdqx58tih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:npm" {...props}></Icon>
