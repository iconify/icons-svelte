<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9k8lxuwq.css';
import '../../css/j/j9ictigtg.css';
import '../../css/h/ht5m2bb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9k8lxuwq"/><path class="j9ictigtg"/><path class="ht5m2bb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cobol-open" {...props}></Icon>
