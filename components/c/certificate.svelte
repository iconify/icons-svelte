<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq7jaobcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq7jaobcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:certificate" {...props}></Icon>
