<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iirs8ac6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iirs8ac6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:honey" {...props}></Icon>
