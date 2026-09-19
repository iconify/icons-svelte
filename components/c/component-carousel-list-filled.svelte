<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho3y81gdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ho3y81gdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-carousel-list-filled" {...props}></Icon>
