<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bez3wqbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bez3wqbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-succeed-outline" {...props}></Icon>
