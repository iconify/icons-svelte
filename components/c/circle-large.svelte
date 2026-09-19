<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpsnj1-mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wpsnj1-mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:circle-large" {...props}></Icon>
