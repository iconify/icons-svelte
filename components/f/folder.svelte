<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s86b8cbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s86b8cbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:folder" {...props}></Icon>
