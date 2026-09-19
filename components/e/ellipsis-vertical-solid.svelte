<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blci9d4-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="blci9d4-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-vertical-solid" {...props}></Icon>
