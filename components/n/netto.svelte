<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k88w72b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k88w72b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:netto" {...props}></Icon>
