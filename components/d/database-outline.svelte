<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q73q2ewlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q73q2ewlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:database-outline" {...props}></Icon>
