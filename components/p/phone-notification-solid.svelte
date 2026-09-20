<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6i98u3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ls6i98u3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-notification-solid" {...props}></Icon>
