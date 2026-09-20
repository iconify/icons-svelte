<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku4lflboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku4lflboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:0-plus" {...props}></Icon>
