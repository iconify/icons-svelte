<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncyvy5epm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ncyvy5epm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bell-outlined" {...props}></Icon>
