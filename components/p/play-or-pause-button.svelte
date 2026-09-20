<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea3mmeb7a.css';
import '../../css/e/ekc3embid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ea3mmeb7a"/><path class="ekc3embid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:play-or-pause-button" {...props}></Icon>
