<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2d4n202r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2d4n202r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:identification-solid" {...props}></Icon>
