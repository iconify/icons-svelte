<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjh4gqbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjh4gqbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:eye-off" {...props}></Icon>
