<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb1ng5b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb1ng5b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:comma" {...props}></Icon>
