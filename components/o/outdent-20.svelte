<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyegqlb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jyegqlb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outdent-20" {...props}></Icon>
