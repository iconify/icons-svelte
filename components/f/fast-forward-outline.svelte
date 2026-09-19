<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4by67b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b4by67b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fast-forward-outline" {...props}></Icon>
