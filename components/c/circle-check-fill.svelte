<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeoc30bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aeoc30bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-check-fill" {...props}></Icon>
