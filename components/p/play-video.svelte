<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm6olf9fp.css';
import '../../css/h/hr6xjbb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zm6olf9fp"/><path class="hr6xjbb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:play-video" {...props}></Icon>
