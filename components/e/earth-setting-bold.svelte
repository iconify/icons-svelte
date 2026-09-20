<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2oou5y1h.css';
import '../../css/j/joldrnb5i.css';
import '../../css/d/ds51e_7li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2oou5y1h"/><path class="joldrnb5i"/><path class="ds51e_7li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:earth-setting-bold" {...props}></Icon>
