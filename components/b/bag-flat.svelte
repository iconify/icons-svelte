<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyca08b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eyca08b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:bag-flat" {...props}></Icon>
