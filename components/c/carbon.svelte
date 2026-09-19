<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2fxoablb.css';
import '../../css/m/mru10lbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h2fxoablb"/><path class="mru10lbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carbon" {...props}></Icon>
