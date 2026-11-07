<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm9nvmbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mm9nvmbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-2-outline" {...props}></Icon>
