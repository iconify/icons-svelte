<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc0fmsbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tc0fmsbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:ci-circle-filled" {...props}></Icon>
