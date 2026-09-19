<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb3g90wjy.css';
import '../../css/s/snfmd8b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb3g90wjy"/><path class="snfmd8b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:boat-sharp" {...props}></Icon>
