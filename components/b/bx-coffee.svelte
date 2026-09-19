<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bebt1abvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bebt1abvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-coffee" {...props}></Icon>
