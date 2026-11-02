<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqggstbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqggstbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-hat-line" {...props}></Icon>
