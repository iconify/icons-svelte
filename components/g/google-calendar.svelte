<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkonhjbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkonhjbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:google-calendar" {...props}></Icon>
