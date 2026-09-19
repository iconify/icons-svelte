<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpp-e2bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dpp-e2bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:lpt" {...props}></Icon>
