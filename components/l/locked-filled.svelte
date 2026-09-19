<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep54zkxas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="ep54zkxas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:locked-filled" {...props}></Icon>
