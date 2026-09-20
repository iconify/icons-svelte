<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek9zqwbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek9zqwbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:augmented-reality-bold" {...props}></Icon>
