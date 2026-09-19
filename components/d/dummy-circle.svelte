<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f20im6pef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f20im6pef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dummy-circle" {...props}></Icon>
