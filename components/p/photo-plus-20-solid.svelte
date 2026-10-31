<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7k8nrb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g7k8nrb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-plus-20-solid" {...props}></Icon>
