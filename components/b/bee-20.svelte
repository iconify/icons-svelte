<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac5rx7nmm.css';
import '../../css/l/lts7tcach.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ac5rx7nmm"/><path class="lts7tcach"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bee-20" {...props}></Icon>
