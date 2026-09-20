<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elzr7jb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elzr7jb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calculator-line" {...props}></Icon>
