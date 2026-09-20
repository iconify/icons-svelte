<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ac-_bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m9ac-_bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:line-x" {...props}></Icon>
