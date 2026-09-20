<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgd02jb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgd02jb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-plus" {...props}></Icon>
