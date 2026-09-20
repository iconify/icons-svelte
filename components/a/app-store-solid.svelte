<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5724xuzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q5724xuzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:app-store-solid" {...props}></Icon>
