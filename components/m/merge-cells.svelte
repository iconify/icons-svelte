<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1up5se8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c1up5se8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:merge-cells" {...props}></Icon>
