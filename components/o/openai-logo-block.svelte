<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhsqq-b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhsqq-b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:openai-logo-block" {...props}></Icon>
