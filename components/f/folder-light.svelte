<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5zhelbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5zhelbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-light" {...props}></Icon>
