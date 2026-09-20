<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz46qppul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iz46qppul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:circle-big" {...props}></Icon>
