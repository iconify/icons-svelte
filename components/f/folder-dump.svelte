<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbt53ppzw.css';
import '../../css/k/krr-sfb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sbt53ppzw"/><path class="krr-sfb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-dump" {...props}></Icon>
