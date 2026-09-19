<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yox13vb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yox13vb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlescrewdriver" {...props}></Icon>
