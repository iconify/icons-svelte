<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4n5v94id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4n5v94id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-left-solid" {...props}></Icon>
