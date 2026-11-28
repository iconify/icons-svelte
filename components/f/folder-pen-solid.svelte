<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abj4bbbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abj4bbbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-pen-solid" {...props}></Icon>
