<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktzn0ftlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="ktzn0ftlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:folder-open-f" {...props}></Icon>
