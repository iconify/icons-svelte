<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upt5e3o1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upt5e3o1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-horizontal-center-filled" {...props}></Icon>
