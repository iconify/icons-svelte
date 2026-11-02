<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mihv603ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mihv603ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-rightbar-close-line" {...props}></Icon>
