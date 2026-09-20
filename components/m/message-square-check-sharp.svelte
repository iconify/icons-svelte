<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq5hl4bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq5hl4bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-check-sharp" {...props}></Icon>
