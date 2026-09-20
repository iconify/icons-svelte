<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9db1vhft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9db1vhft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-rightbar-close-line" {...props}></Icon>
