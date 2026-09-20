<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssw7l0b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssw7l0b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:adroll" {...props}></Icon>
