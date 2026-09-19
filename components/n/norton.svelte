<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea1bd19wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea1bd19wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:norton" {...props}></Icon>
