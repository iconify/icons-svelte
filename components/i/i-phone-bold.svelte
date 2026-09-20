<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqo1lcfqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqo1lcfqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:i-phone-bold" {...props}></Icon>
