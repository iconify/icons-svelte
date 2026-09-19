<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txqggkbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txqggkbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:clone" {...props}></Icon>
