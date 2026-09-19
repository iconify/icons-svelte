<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9ywuf_1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="v9ywuf_1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:label-hogwarts" {...props}></Icon>
