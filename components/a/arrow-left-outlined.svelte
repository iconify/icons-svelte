<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4wm5dt-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z4wm5dt-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:arrow-left-outlined" {...props}></Icon>
