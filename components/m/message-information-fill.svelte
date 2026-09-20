<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfcjhcclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfcjhcclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-information-fill" {...props}></Icon>
