<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p36imds9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p36imds9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:groupme" {...props}></Icon>
