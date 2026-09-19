<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwop6eh_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwop6eh_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:pan" {...props}></Icon>
