<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap9ynib2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ap9ynib2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:medical-cross-symbol-solid" {...props}></Icon>
