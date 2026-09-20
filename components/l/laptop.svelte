<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dse1e7dvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dse1e7dvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:laptop" {...props}></Icon>
