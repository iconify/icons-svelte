<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjmg4z__o.css';
import '../../css/d/d1jue8bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sjmg4z__o"/><path class="d1jue8bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:pet-animals-turtle" {...props}></Icon>
