<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r64whbh1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="r64whbh1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:clock-f" {...props}></Icon>
