<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egs52obej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egs52obej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:italic" {...props}></Icon>
