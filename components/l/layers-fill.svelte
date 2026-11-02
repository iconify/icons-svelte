<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpusvrhxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpusvrhxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layers-fill" {...props}></Icon>
