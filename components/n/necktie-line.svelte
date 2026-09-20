<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3k9a95ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3k9a95ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:necktie-line" {...props}></Icon>
