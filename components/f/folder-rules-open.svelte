<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixetddbeg.css';
import '../../css/w/w_b6j-_2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixetddbeg"/><path class="w_b6j-_2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-rules-open" {...props}></Icon>
