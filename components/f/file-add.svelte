<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue5dmkb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue5dmkb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-add" {...props}></Icon>
