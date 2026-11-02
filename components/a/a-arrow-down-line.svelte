<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5pgpp91l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5pgpp91l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:a-arrow-down-line" {...props}></Icon>
