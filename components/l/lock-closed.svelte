<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4kkrfgux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z4kkrfgux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:lock-closed" {...props}></Icon>
