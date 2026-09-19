<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eznpw-5ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":898,"height":1024};
const content = `<path class="eznpw-5ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:nodejs" {...props}></Icon>
