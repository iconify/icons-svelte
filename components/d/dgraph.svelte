<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tumy6cd7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tumy6cd7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dgraph" {...props}></Icon>
