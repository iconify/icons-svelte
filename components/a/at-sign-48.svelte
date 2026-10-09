<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3eacdoxs.css';
import '../../css/m/m9i0cybsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j3eacdoxs"/><path class="m9i0cybsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:at-sign-48" {...props}></Icon>
