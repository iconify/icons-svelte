<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1c1n3btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1c1n3btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codeceptjs" {...props}></Icon>
