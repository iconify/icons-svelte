<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awhk9db1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awhk9db1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:corner-double-left-down" {...props}></Icon>
