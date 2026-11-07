<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo0xsojdd.css';
import '../../css/o/o4sar_bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo0xsojdd"/><path clip-rule="evenodd" class="o4sar_bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-dropped-rounded-outline" {...props}></Icon>
