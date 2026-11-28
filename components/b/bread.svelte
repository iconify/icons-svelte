<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/embr9hbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="embr9hbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bread" {...props}></Icon>
