<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjcmjo8jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjcmjo8jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:power-force-shutdown" {...props}></Icon>
