<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7obs5b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l7obs5b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:history-outline" {...props}></Icon>
