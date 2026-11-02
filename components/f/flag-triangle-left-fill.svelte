<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5-a49vjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5-a49vjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-triangle-left-fill" {...props}></Icon>
