<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stk0jfp5a.css';
import '../../css/s/sjc8stbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":196,"height":256};
const content = `<path class="stk0jfp5a"/><path class="sjc8stbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:afordin-light" {...props}></Icon>
