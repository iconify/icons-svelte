<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elp4ijr-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elp4ijr-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-6-fill" {...props}></Icon>
