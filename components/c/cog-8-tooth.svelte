<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjmase5-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bjmase5-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cog-8-tooth" {...props}></Icon>
