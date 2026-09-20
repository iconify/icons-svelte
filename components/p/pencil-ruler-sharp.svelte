<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cofugbb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cofugbb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pencil-ruler-sharp" {...props}></Icon>
