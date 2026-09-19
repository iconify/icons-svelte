<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar355_tpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ar355_tpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:cluster-outlined" {...props}></Icon>
