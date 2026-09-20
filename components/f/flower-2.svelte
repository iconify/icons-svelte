<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs4r2bbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="bs4r2bbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flower-2" {...props}></Icon>
