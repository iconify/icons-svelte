<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk0kkab0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk0kkab0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-text-lock" {...props}></Icon>
