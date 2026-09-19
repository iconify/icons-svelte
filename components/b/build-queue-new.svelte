<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx4yyckre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tx4yyckre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:build-queue-new" {...props}></Icon>
