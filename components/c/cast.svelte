<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oatqgi0zs.css';
import '../../css/c/c5-yaz5ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oatqgi0zs"/><path class="c5-yaz5ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cast" {...props}></Icon>
