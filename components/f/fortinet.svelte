<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emg_5vb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emg_5vb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fortinet" {...props}></Icon>
