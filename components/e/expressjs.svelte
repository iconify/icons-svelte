<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcdlnf99m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcdlnf99m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:expressjs" {...props}></Icon>
