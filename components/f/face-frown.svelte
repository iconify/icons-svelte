<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wye99bcnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wye99bcnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:face-frown" {...props}></Icon>
