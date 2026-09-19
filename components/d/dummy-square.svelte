<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-nt3clhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-nt3clhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dummy-square" {...props}></Icon>
