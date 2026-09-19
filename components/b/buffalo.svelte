<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm-3jmkwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":3035,"height":634};
const content = `<path class="fm-3jmkwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:buffalo" {...props}></Icon>
