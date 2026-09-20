<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3o1dcc0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3o1dcc0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:datacamp" {...props}></Icon>
