<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b07s0zb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b07s0zb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:okta" {...props}></Icon>
