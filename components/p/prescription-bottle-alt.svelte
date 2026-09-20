<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7yu7jbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f7yu7jbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:prescription-bottle-alt" {...props}></Icon>
