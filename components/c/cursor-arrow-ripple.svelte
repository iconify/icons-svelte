<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqn8tyz7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lqn8tyz7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cursor-arrow-ripple" {...props}></Icon>
