<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmj1afbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmj1afbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:facebook-square" {...props}></Icon>
