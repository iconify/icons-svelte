<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8nu7c66p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x8nu7c66p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:link-slash-20-solid" {...props}></Icon>
