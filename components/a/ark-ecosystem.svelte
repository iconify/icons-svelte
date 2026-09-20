<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btc7y3bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btc7y3bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ark-ecosystem" {...props}></Icon>
