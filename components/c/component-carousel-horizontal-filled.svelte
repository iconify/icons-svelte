<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4hgxccys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4hgxccys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-carousel-horizontal-filled" {...props}></Icon>
