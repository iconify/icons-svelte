<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-mjqqb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c-mjqqb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrows-up-down" {...props}></Icon>
