<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvatpob0r.css';
import '../../css/g/g9wb33bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvatpob0r"/><path class="g9wb33bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-minus-alt-filled" {...props}></Icon>
