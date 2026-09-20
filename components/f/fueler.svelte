<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kio867beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kio867beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fueler" {...props}></Icon>
