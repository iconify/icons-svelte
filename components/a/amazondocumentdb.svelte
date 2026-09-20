<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmds795_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmds795_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazondocumentdb" {...props}></Icon>
