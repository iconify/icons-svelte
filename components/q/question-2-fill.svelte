<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgkvktvjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgkvktvjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:question-2-fill" {...props}></Icon>
