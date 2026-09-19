<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hydl6x73v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hydl6x73v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:percentage" {...props}></Icon>
