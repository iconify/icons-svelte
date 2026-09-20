<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc-3-bc9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gc-3-bc9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bolt-circle-bold" {...props}></Icon>
