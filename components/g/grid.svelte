<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_je1b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in_je1b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:grid" {...props}></Icon>
