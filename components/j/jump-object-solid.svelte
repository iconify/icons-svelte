<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be0lh-30x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="be0lh-30x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:jump-object-solid" {...props}></Icon>
