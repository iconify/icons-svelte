<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of7v_qbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="of7v_qbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-horiz-center-detailed-fill" {...props}></Icon>
