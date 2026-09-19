<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgeipghhv.css';
import '../../css/n/npf-mpbxr.css';
import '../../css/c/cofxwr0zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kgeipghhv"/><path class="npf-mpbxr"/><path class="cofxwr0zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:database-twotone" {...props}></Icon>
