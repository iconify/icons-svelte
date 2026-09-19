<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zurmcyjfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zurmcyjfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid-small-round" {...props}></Icon>
