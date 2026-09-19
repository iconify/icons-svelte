<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg1q9abne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jg1q9abne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:lock-open" {...props}></Icon>
