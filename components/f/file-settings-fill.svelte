<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cokea7syv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cokea7syv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-settings-fill" {...props}></Icon>
