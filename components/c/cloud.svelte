<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9wan6knc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m9wan6knc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:cloud" {...props}></Icon>
