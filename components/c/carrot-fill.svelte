<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1wrvac7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1wrvac7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:carrot-fill" {...props}></Icon>
