<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uimoi1b4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uimoi1b4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:copies-small-filled" {...props}></Icon>
