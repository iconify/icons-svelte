<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl3j3lu6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl3j3lu6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-tree-solid" {...props}></Icon>
