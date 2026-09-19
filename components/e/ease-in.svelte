<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txpoe7bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txpoe7bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ease-in" {...props}></Icon>
