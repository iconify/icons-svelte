<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9goa4bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g9goa4bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-arrow-down-solid" {...props}></Icon>
