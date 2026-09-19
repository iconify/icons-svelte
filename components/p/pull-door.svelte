<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obua1kb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="obua1kb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pull-door" {...props}></Icon>
