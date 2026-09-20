<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s940n5tlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s940n5tlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-circle-bold" {...props}></Icon>
