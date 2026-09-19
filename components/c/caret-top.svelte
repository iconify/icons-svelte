<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3yq9f4rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g3yq9f4rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:caret-top" {...props}></Icon>
