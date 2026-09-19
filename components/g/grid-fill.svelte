<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl-ql3bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl-ql3bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:grid-fill" {...props}></Icon>
