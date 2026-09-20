<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of5hlmbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of5hlmbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:folder-remove" {...props}></Icon>
