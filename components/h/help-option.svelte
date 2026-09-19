<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1hxhfb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1hxhfb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:help-option" {...props}></Icon>
