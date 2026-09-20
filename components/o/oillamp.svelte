<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8z9q-b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b8z9q-b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:oillamp" {...props}></Icon>
