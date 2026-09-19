<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukbuipb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukbuipb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-friends" {...props}></Icon>
