<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhirkpb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hhirkpb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:external-link" {...props}></Icon>
