<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5xic8bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b5xic8bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:color-swatch" {...props}></Icon>
