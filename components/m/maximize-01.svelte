<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebce-tb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebce-tb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:maximize-01" {...props}></Icon>
