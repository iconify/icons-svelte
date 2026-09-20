<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_xoe9j3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_xoe9j3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-add" {...props}></Icon>
