<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o97im9hdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":24};
const content = `<path class="o97im9hdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:facebook" {...props}></Icon>
