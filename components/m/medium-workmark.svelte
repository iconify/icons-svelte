<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emn7phbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="emn7phbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:medium-workmark" {...props}></Icon>
