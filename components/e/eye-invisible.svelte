<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjqyt7b_n.css';
import '../../css/g/gi_7ztbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pjqyt7b_n"/><path class="gi_7ztbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:eye-invisible" {...props}></Icon>
