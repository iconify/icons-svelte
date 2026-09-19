<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoaza3xsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aoaza3xsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:fire-solid" {...props}></Icon>
