<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok9qob__s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ok9qob__s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:canvas" {...props}></Icon>
