<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrjb4xbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrjb4xbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:check" {...props}></Icon>
