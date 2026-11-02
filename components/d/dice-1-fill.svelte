<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv7mh-bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv7mh-bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dice-1-fill" {...props}></Icon>
