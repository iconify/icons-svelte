<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4hxffrur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="i4hxffrur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:circle" {...props}></Icon>
