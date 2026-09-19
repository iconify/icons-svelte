<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqw7-8bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uqw7-8bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:bitbucket" {...props}></Icon>
