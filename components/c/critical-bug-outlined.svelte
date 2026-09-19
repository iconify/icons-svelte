<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zctbc7m.css';
import '../../css/j/jw5g59skx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zctbc7m"/><path class="jw5g59skx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:critical-bug-outlined" {...props}></Icon>
