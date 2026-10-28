<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hka0krbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hka0krbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-ruler" {...props}></Icon>
