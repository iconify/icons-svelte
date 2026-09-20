<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5g_1949x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5g_1949x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hat-glasses-sharp" {...props}></Icon>
