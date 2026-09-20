<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajwjw6b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ajwjw6b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-up-circle" {...props}></Icon>
