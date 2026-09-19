<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlnn0ibiz.css';
import '../../css/t/txfhqbbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nlnn0ibiz"/><path class="txfhqbbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:location" {...props}></Icon>
