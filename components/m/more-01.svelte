<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfrcibb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfrcibb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-01" {...props}></Icon>
