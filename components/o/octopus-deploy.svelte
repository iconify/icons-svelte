<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcerrwbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcerrwbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:octopus-deploy" {...props}></Icon>
