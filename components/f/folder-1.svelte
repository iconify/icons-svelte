<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsljxnill.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsljxnill"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:folder-1" {...props}></Icon>
