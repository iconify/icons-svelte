<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u861_z2tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u861_z2tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:react-table" {...props}></Icon>
