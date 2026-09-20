<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmu6qlb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmu6qlb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kotlin-logo" {...props}></Icon>
