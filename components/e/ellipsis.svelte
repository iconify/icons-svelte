<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqrapilox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqrapilox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ellipsis" {...props}></Icon>
