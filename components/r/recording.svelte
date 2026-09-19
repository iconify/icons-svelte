<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b93j9cbjr.css';
import '../../css/m/mbcglytpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b93j9cbjr"/><path class="mbcglytpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:recording" {...props}></Icon>
