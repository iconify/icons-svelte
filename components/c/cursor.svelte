<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpcumh7bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="zpcumh7bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:cursor" {...props}></Icon>
