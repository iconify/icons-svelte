<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmj4gbbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nmj4gbbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:airplane" {...props}></Icon>
