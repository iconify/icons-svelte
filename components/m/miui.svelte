<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp_i_kw1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="wp_i_kw1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:miui" {...props}></Icon>
