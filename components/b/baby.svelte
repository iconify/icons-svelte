<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfjn-7gcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjn-7gcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:baby" {...props}></Icon>
