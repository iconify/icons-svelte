<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlnuinbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qlnuinbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:close-up-mode" {...props}></Icon>
