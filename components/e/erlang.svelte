<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt_0hdbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qt_0hdbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:erlang" {...props}></Icon>
