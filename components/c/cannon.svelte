<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqbk1mbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="qqbk1mbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cannon" {...props}></Icon>
