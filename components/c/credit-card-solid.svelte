<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy8l_xb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uy8l_xb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:credit-card-solid" {...props}></Icon>
