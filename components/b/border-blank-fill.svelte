<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el1q76mqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el1q76mqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-blank-fill" {...props}></Icon>
