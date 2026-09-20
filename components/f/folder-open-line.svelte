<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx0vb0m6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx0vb0m6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-open-line" {...props}></Icon>
