<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw28llotl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw28llotl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:folder-plus" {...props}></Icon>
