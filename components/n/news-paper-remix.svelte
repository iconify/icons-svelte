<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzjez2a4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jzjez2a4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:news-paper-remix" {...props}></Icon>
