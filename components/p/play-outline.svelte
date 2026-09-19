<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz28_8bzx.css';
import '../../css/b/b93j9cbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gz28_8bzx"/><path class="b93j9cbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:play-outline" {...props}></Icon>
