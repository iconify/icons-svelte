<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhlr7h7su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhlr7h7su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chrysler" {...props}></Icon>
