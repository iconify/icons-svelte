<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw7dfbv7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jw7dfbv7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:glove" {...props}></Icon>
