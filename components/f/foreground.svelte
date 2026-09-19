<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r90syqbvp.css';
import '../../css/j/jcmaqeb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r90syqbvp"/><path class="jcmaqeb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:foreground" {...props}></Icon>
