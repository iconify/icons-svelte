<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmwyj3bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmwyj3bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:newsvine-logo-solid" {...props}></Icon>
