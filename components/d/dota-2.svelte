<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dazllrb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dazllrb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dota-2" {...props}></Icon>
