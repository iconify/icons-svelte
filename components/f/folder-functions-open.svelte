<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9k8lxuwq.css';
import '../../css/g/g-7edib4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9k8lxuwq"/><path class="g-7edib4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-functions-open" {...props}></Icon>
