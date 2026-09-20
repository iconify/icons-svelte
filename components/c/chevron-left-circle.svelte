<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8rxfu3fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8rxfu3fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-left-circle" {...props}></Icon>
