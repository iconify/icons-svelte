<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4dpc3bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dpc3bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:border-clear" {...props}></Icon>
