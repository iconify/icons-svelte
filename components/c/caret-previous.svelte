<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi2utgblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2utgblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:caret-previous" {...props}></Icon>
