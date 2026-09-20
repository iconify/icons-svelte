<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwpfszb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwpfszb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:bin-2" {...props}></Icon>
