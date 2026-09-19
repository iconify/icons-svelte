<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by5xilmjq.css';
import '../../css/t/t6wz8cb3t.css';
import '../../css/a/aozro6bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="by5xilmjq"/><circle class="t6wz8cb3t"/><circle class="aozro6bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:ellipsis-filled" {...props}></Icon>
