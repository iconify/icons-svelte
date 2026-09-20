<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkw77b62j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkw77b62j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blogger-logo-bold" {...props}></Icon>
