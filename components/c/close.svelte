<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/matrm2b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="matrm2b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:close" {...props}></Icon>
