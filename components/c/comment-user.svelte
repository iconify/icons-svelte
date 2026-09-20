<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7ce7h84x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="d7ce7h84x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:comment-user" {...props}></Icon>
