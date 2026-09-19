<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe8pdjbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe8pdjbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:aggregate" {...props}></Icon>
