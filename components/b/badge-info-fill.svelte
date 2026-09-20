<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue1e12bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ue1e12bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-info-fill" {...props}></Icon>
