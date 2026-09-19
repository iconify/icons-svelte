<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b26cuwy7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b26cuwy7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:phone-outlined" {...props}></Icon>
