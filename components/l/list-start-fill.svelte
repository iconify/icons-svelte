<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afz92zvrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afz92zvrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-start-fill" {...props}></Icon>
