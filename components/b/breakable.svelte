<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgt5jg9jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="dgt5jg9jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:breakable" {...props}></Icon>
