<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c61wmobzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c61wmobzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-info-round-fill" {...props}></Icon>
