<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd75nn-_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd75nn-_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:eye-closed-solid" {...props}></Icon>
