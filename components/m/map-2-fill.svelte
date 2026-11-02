<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc21p692x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc21p692x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-2-fill" {...props}></Icon>
