<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoc5fqv5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoc5fqv5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-heart-sharp" {...props}></Icon>
