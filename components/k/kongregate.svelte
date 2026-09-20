<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffqldcc1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffqldcc1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kongregate" {...props}></Icon>
