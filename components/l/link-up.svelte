<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av0tnr0ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av0tnr0ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:link-up" {...props}></Icon>
