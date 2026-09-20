<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyte-2bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-1.5};
const content = `<path class="pyte-2bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:phone-f" {...props}></Icon>
