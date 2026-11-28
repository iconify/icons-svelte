<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_jysbxzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_jysbxzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pill-bottle-check" {...props}></Icon>
