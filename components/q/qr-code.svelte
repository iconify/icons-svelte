<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5nrsz3rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5nrsz3rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:qr-code" {...props}></Icon>
