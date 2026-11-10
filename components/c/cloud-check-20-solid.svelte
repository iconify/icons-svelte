<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9zz1bb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j9zz1bb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-check-20-solid" {...props}></Icon>
