<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8mordb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8mordb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-stack-outline" {...props}></Icon>
