<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ess69bcms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ess69bcms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:full-screen-square-bold" {...props}></Icon>
