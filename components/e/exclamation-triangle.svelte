<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbamd212o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hbamd212o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:exclamation-triangle" {...props}></Icon>
