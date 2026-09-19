<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcb3-fmrh.css';
import '../../css/w/w74cijboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bcb3-fmrh"/><path class="w74cijboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:field-time-outlined" {...props}></Icon>
