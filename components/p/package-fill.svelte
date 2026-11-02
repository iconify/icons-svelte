<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc6m9fbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc6m9fbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:package-fill" {...props}></Icon>
