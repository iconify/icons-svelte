<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a04an4bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a04an4bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mx-linux" {...props}></Icon>
