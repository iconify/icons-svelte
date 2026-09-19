<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g73t8rbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g73t8rbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:octoloaderempty" {...props}></Icon>
