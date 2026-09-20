<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inov2jebv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inov2jebv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:folder-solid" {...props}></Icon>
