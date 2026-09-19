<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9fgmvbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9fgmvbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:mobile-phone-outline" {...props}></Icon>
