<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_jj1gxap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="d_jj1gxap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:folder-open-32" {...props}></Icon>
