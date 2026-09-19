<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cny_l1kll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="cny_l1kll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:certificatethree" {...props}></Icon>
