<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7pkitbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7pkitbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bed-flat-filled" {...props}></Icon>
