<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akni7yb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akni7yb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dlna" {...props}></Icon>
