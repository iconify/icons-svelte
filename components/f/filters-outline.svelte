<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoptiib_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoptiib_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filters-outline" {...props}></Icon>
