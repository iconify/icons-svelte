<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zavsg-4bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zavsg-4bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ember" {...props}></Icon>
