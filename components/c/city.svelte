<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bem_48t0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bem_48t0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:city" {...props}></Icon>
