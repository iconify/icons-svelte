<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt8cwocyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pt8cwocyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:quarterstaff" {...props}></Icon>
