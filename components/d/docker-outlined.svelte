<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osh-gp4ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="osh-gp4ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:docker-outlined" {...props}></Icon>
