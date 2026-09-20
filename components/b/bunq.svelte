<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thygd8drw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thygd8drw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bunq" {...props}></Icon>
