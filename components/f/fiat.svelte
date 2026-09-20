<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-f68p8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7-f68p8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fiat" {...props}></Icon>
