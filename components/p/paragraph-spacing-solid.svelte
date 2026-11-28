<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxxo35b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxo35b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:paragraph-spacing-solid" {...props}></Icon>
