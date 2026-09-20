<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odfhc8bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odfhc8bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comments-2-line" {...props}></Icon>
