<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofkb0xw0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofkb0xw0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-narrow-wide-solid" {...props}></Icon>
