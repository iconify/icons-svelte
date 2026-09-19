<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e70c6kqeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e70c6kqeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airport" {...props}></Icon>
