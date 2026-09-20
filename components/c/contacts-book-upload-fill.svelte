<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtot7pbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtot7pbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-upload-fill" {...props}></Icon>
