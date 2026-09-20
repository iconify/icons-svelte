<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb7hj8bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb7hj8bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:barmenia" {...props}></Icon>
