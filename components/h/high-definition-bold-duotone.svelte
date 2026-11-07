<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/n/n74totb4p.css';
import '../../css/c/cdl9xjyfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="n74totb4p"/><path clip-rule="evenodd" class="cdl9xjyfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:high-definition-bold-duotone" {...props}></Icon>
