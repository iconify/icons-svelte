<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6rqqdb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6rqqdb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-triangle-up-filled" {...props}></Icon>
