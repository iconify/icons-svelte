<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyrjo7r-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyrjo7r-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dimond-alt" {...props}></Icon>
