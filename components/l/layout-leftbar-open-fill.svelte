<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hby3n6ass.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hby3n6ass"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-leftbar-open-fill" {...props}></Icon>
