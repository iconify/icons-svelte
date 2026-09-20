<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n476uizha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n476uizha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fire-hydrant-off" {...props}></Icon>
