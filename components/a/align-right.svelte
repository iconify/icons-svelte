<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv0akdb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv0akdb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:align-right" {...props}></Icon>
