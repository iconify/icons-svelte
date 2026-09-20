<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb56rqbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb56rqbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-alt-4-fill" {...props}></Icon>
