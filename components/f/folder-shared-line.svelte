<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksf93nojb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksf93nojb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-shared-line" {...props}></Icon>
