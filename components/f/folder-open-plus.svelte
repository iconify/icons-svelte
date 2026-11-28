<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqrqgxblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrqgxblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-open-plus" {...props}></Icon>
