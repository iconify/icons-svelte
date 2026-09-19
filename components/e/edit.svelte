<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5n66-bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g5n66-bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:edit" {...props}></Icon>
