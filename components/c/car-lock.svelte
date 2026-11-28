<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kajvry29a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kajvry29a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:car-lock" {...props}></Icon>
