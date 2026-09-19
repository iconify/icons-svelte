<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui2tq9n4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ui2tq9n4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:clothes-pants-short" {...props}></Icon>
