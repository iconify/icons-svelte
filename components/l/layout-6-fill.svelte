<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-sdhdcww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-sdhdcww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-6-fill" {...props}></Icon>
