<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szr2kr31a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szr2kr31a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:briefcase-x" {...props}></Icon>
