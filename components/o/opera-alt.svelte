<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvesc-9me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvesc-9me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:opera-alt" {...props}></Icon>
