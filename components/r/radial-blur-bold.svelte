<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uak_0hbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uak_0hbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radial-blur-bold" {...props}></Icon>
