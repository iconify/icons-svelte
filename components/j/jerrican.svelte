<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km1sp5-1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="km1sp5-1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:jerrican" {...props}></Icon>
