<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqr3isbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dqr3isbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:desktop-download" {...props}></Icon>
