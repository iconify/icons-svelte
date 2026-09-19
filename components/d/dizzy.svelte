<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8ws9tb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="n8ws9tb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:dizzy" {...props}></Icon>
