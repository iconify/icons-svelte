<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at7kl5b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="at7kl5b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-x-filled" {...props}></Icon>
