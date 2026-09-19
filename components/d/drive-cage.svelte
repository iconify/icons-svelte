<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3n6gqc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3n6gqc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:drive-cage" {...props}></Icon>
