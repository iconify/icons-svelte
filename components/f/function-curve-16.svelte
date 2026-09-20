<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgsw9d_7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bgsw9d_7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:function-curve-16" {...props}></Icon>
