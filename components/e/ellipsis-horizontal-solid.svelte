<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia9ptx4wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia9ptx4wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal-solid" {...props}></Icon>
