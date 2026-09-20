<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maer_5kur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maer_5kur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:button-pointer" {...props}></Icon>
