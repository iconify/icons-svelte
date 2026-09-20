<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9v41_qpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9v41_qpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:direction-alt-3-fill" {...props}></Icon>
