<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxqd5xezl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxqd5xezl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:remark" {...props}></Icon>
