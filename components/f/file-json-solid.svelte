<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw7ckwbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw7ckwbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-json-solid" {...props}></Icon>
