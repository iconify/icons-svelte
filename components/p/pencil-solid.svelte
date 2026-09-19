<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jacn1v9zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jacn1v9zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pencil-solid" {...props}></Icon>
