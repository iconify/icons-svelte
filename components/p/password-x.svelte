<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5fj_c4mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5fj_c4mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:password-x" {...props}></Icon>
