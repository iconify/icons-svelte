<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovucfdc3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovucfdc3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:carets-up-down" {...props}></Icon>
