<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh3_ei7nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3_ei7nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:move-light" {...props}></Icon>
