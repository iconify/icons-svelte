<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z361xccom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z361xccom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-solid" {...props}></Icon>
