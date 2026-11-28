<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jazetjb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jazetjb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-closed-solid" {...props}></Icon>
