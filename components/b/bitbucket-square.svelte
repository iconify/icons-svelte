<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b568kobcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="b568kobcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bitbucket-square" {...props}></Icon>
