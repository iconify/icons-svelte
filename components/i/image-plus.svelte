<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4j-itpzn.css';
import '../../css/w/wch9wu0eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4j-itpzn"/><path class="wch9wu0eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-plus" {...props}></Icon>
