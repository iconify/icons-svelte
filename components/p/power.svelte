<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhzd0mb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhzd0mb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:power" {...props}></Icon>
