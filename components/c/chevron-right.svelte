<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj7raux_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj7raux_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevron-right" {...props}></Icon>
