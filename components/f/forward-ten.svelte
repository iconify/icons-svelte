<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_fujtsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia_fujtsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:forward-ten" {...props}></Icon>
