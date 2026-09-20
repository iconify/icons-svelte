<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqylbgb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqylbgb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gowalla-logo-4-solid" {...props}></Icon>
