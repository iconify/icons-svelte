<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jli2whjga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jli2whjga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-alert-outline" {...props}></Icon>
