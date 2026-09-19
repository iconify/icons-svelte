<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piynuegax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="piynuegax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:plus-circle" {...props}></Icon>
