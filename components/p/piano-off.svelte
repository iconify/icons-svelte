<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecpj7nrdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecpj7nrdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:piano-off" {...props}></Icon>
