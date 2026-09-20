<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6jc2nbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6jc2nbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nim" {...props}></Icon>
