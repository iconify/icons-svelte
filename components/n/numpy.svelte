<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9r9x7bay.css';
import '../../css/y/y3q6sjb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d9r9x7bay"/><path class="y3q6sjb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:numpy" {...props}></Icon>
