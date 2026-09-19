<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5bwxtbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5bwxtbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cloud-upload" {...props}></Icon>
