<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv2isybhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":640};
const content = `<path class="gv2isybhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:image" {...props}></Icon>
