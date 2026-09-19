<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0hy2rb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0hy2rb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-objects-horizontal-left" {...props}></Icon>
