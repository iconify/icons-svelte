<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9v3s6lts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q9v3s6lts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:radioactive-2-remix" {...props}></Icon>
