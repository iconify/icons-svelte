<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4806ne8v.css';
import '../../css/j/jbx312dhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4806ne8v"/><path class="jbx312dhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:coin-solid" {...props}></Icon>
