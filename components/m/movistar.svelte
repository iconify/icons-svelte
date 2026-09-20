<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maaver_gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maaver_gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:movistar" {...props}></Icon>
