<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jglg2ik2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jglg2ik2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-circle-right" {...props}></Icon>
