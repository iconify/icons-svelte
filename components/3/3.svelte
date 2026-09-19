<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx5403b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":772};
const content = `<path class="dx5403b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:3" {...props}></Icon>
