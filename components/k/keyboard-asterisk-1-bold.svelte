<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehtfmd7by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehtfmd7by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:keyboard-asterisk-1-bold" {...props}></Icon>
