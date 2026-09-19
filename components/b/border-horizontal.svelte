<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5ffo1bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ffo1bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-horizontal" {...props}></Icon>
