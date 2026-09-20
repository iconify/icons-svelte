<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr94q88qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr94q88qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fluent" {...props}></Icon>
