<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii9pev65x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii9pev65x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:blinds" {...props}></Icon>
