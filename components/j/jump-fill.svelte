<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb71i3b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb71i3b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jump-fill" {...props}></Icon>
