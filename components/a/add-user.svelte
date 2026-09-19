<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3na2nb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3na2nb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:add-user" {...props}></Icon>
