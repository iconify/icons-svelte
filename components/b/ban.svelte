<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py9j02b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py9j02b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:ban" {...props}></Icon>
