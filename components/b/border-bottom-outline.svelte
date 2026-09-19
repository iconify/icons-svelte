<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llg57ea4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="llg57ea4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:border-bottom-outline" {...props}></Icon>
