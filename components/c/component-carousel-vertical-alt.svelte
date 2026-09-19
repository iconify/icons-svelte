<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzkaqpb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzkaqpb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-carousel-vertical-alt" {...props}></Icon>
