<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj7-q5b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj7-q5b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:caret-down-fill" {...props}></Icon>
