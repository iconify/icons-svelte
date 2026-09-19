<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi0-5b3gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi0-5b3gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:divide-solid" {...props}></Icon>
