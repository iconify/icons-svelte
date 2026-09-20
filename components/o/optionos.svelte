<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eulpr3bjr.css';
import '../../css/r/rw8aspbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eulpr3bjr"/><path class="rw8aspbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:optionos" {...props}></Icon>
