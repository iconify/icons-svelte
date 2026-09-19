<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/extgyq5ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="extgyq5ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fit-to-screen" {...props}></Icon>
