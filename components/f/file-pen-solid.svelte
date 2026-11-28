<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu3ugdc7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu3ugdc7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-pen-solid" {...props}></Icon>
