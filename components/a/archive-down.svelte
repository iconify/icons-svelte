<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajvynsb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajvynsb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive-down" {...props}></Icon>
