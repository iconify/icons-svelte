<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odlgx4b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="odlgx4b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:circle-16" {...props}></Icon>
