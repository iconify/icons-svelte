<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixexqn-8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ixexqn-8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:command-prompt" {...props}></Icon>
