<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9h68pkmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9h68pkmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flag-alt-3" {...props}></Icon>
