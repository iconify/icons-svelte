<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba-w97ous.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba-w97ous"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-plus" {...props}></Icon>
