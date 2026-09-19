<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lawl0y4tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lawl0y4tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:maps-go-straight" {...props}></Icon>
