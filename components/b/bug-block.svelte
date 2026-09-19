<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa7lk71xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qa7lk71xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bug-block" {...props}></Icon>
