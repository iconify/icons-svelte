<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_jkxovpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_jkxovpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:link-alt" {...props}></Icon>
