<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w361a4i3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w361a4i3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:catalog" {...props}></Icon>
