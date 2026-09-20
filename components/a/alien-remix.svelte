<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni47v0btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ni47v0btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:alien-remix" {...props}></Icon>
