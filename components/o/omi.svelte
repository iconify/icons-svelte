<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol67_6b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol67_6b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:omi" {...props}></Icon>
