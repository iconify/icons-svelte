<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyhl03b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhl03b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-open-fill" {...props}></Icon>
