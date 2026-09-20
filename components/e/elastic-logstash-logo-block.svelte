<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz0xl4pup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz0xl4pup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-logstash-logo-block" {...props}></Icon>
