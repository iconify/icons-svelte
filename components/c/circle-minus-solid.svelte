<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huwz9vbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="huwz9vbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:circle-minus-solid" {...props}></Icon>
