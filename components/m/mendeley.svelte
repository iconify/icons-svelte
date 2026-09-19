<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3h0yyeyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e3h0yyeyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mendeley" {...props}></Icon>
