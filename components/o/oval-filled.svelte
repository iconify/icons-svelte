<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8w9zmb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8w9zmb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:oval-filled" {...props}></Icon>
