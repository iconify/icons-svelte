<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbk83jwqy.css';
import '../../css/c/cbhrk9bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbk83jwqy"/><path class="cbhrk9bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pin-location" {...props}></Icon>
