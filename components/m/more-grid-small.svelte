<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwixg__8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwixg__8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:more-grid-small" {...props}></Icon>
