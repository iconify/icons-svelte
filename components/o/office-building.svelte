<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6n2v-bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b6n2v-bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:office-building" {...props}></Icon>
