<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de5-ioblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="de5-ioblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:danger-circle-bold" {...props}></Icon>
