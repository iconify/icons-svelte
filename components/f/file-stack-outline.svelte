<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exyoo0b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="exyoo0b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-stack-outline" {...props}></Icon>
