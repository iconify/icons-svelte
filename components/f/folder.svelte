<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz12_jbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cz12_jbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:folder" {...props}></Icon>
