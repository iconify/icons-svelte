<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu89hqblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu89hqblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:gift" {...props}></Icon>
