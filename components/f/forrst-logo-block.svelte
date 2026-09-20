<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9flx59id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9flx59id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:forrst-logo-block" {...props}></Icon>
