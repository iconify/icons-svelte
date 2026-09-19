<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj879bbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":1024};
const content = `<path class="jj879bbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mobile" {...props}></Icon>
