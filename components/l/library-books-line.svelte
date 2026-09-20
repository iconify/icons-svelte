<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5t9tb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5t9tb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:library-books-line" {...props}></Icon>
