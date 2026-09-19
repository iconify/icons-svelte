<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwbi8czbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwbi8czbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-template" {...props}></Icon>
