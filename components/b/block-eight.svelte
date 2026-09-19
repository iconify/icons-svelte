<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbx1--m4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hbx1--m4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-eight" {...props}></Icon>
