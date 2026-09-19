<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb1xkjbuo.css';
import '../../css/y/yg7xgph3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mb1xkjbuo"/><path class="yg7xgph3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:notebook" {...props}></Icon>
