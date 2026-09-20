<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1v0vkkgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="v1v0vkkgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-left" {...props}></Icon>
