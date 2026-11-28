<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qojzlrxcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qojzlrxcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-text-solid" {...props}></Icon>
