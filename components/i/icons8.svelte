<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp0o-snjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp0o-snjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:icons8" {...props}></Icon>
