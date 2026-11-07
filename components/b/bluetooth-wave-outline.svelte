<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z520fs12r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z520fs12r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-wave-outline" {...props}></Icon>
