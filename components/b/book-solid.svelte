<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd1q9wb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd1q9wb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:book-solid" {...props}></Icon>
