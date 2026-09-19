<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5ulpsbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5ulpsbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:options-horizontal" {...props}></Icon>
