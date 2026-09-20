<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iecc9yb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iecc9yb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pearson" {...props}></Icon>
