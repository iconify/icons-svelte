<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4qu6ekcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4qu6ekcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:minus" {...props}></Icon>
