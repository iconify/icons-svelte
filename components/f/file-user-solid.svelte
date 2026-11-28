<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ff2wuha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ff2wuha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-user-solid" {...props}></Icon>
