<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cek6ewbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="cek6ewbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:add" {...props}></Icon>
