<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywuvlsy5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywuvlsy5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-u-turn-right-sharp" {...props}></Icon>
