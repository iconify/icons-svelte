<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw28ws39f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw28ws39f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lode" {...props}></Icon>
