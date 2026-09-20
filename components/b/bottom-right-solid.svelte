<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6b6rrbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i6b6rrbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bottom-right-solid" {...props}></Icon>
