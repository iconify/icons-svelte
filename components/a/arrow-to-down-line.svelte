<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phvm0umma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phvm0umma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-down-line" {...props}></Icon>
