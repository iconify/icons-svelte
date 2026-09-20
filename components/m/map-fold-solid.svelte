<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9hu36b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v9hu36b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:map-fold-solid" {...props}></Icon>
