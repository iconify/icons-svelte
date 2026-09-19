<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oke1umbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oke1umbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cylinder" {...props}></Icon>
