<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9y-kw0_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9y-kw0_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fridge" {...props}></Icon>
