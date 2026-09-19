<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ffhfu6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ffhfu6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bold" {...props}></Icon>
