<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clg8mbq-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clg8mbq-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-euro-fill" {...props}></Icon>
