<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knxbbqb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="knxbbqb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:flask-round-bottom-empty" {...props}></Icon>
