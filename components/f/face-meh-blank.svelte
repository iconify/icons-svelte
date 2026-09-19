<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyw2gn6tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fyw2gn6tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-meh-blank" {...props}></Icon>
