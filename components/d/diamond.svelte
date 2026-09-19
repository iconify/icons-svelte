<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk6phkbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk6phkbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:diamond" {...props}></Icon>
