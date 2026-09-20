<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu-2o-b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu-2o-b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:anchor-logo-block" {...props}></Icon>
