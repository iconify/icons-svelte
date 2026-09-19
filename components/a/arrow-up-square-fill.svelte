<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qan7z0bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qan7z0bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-square-fill" {...props}></Icon>
