<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krsh2zb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krsh2zb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:factory-solid" {...props}></Icon>
