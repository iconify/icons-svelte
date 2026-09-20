<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-b_krv-u.css';
import '../../css/s/s99lf0bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-b_krv-u"/><path class="s99lf0bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indent-decrease-line" {...props}></Icon>
