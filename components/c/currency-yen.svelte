<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxmoirb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxmoirb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-yen" {...props}></Icon>
