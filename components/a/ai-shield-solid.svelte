<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsxcxqbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxcxqbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-shield-solid" {...props}></Icon>
