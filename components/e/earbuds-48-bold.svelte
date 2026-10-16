<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds6kzrfzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ds6kzrfzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earbuds-48-bold" {...props}></Icon>
