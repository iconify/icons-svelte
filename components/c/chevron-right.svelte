<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c791wyter.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c791wyter"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-right" {...props}></Icon>
