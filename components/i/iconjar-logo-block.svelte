<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x__ihteae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x__ihteae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iconjar-logo-block" {...props}></Icon>
