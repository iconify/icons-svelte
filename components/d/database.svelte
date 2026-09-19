<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj200ab6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jj200ab6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:database" {...props}></Icon>
