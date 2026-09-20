<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0831wbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ln0831wbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-wearing-dress-beside-broadshouldered-person-standing" {...props}></Icon>
