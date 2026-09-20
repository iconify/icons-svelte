<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz-1x0bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz-1x0bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jrgroup" {...props}></Icon>
