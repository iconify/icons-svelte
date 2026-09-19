<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhg4nbcno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhg4nbcno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:medium" {...props}></Icon>
