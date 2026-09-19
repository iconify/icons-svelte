<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1v8db0po.css';
import '../../css/b/bo9dr7buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1v8db0po"/><path class="bo9dr7buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:flag-checkered" {...props}></Icon>
