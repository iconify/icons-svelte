<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b039fzbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b039fzbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:at" {...props}></Icon>
