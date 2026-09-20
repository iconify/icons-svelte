<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2vr2vnyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2vr2vnyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:filter-list-fill" {...props}></Icon>
