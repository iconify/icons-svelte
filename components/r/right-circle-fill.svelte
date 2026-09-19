<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofj_3-bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ofj_3-bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:right-circle-fill" {...props}></Icon>
