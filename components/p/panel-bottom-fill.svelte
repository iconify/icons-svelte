<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xebuqdn9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xebuqdn9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-bottom-fill" {...props}></Icon>
