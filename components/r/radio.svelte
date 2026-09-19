<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irm3f4b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="irm3f4b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:radio" {...props}></Icon>
