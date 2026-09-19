<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pozm4jbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pozm4jbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cms" {...props}></Icon>
