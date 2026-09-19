<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljlykjvhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ljlykjvhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:rocket-outline" {...props}></Icon>
