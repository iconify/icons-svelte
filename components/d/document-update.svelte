<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0s08bcuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0s08bcuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-update" {...props}></Icon>
