<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdqndac6f.css';
import '../../css/u/ulfd5d-am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdqndac6f"/><circle class="ulfd5d-am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-nuclear" {...props}></Icon>
