<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uikwfibns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uikwfibns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:refined-github" {...props}></Icon>
