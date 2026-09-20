<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugoglub7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugoglub7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-lines-fill" {...props}></Icon>
