<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe3cn1bfd.css';
import '../../css/i/i2k121bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe3cn1bfd"/><path class="i2k121bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:radio-circle-marked" {...props}></Icon>
