<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u82pom1na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u82pom1na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-volleyball" {...props}></Icon>
