<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj8jzub4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj8jzub4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:console" {...props}></Icon>
