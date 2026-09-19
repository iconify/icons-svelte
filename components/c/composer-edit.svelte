<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnglojbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dnglojbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:composer-edit" {...props}></Icon>
