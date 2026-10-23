<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw0gb-6bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw0gb-6bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rectangle-circle" {...props}></Icon>
