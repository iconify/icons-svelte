<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta9oqnbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ta9oqnbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:calendar-number-sharp" {...props}></Icon>
