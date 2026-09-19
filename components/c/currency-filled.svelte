<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqhslzb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqhslzb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-filled" {...props}></Icon>
