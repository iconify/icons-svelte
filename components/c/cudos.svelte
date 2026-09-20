<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_at2po4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_at2po4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cudos" {...props}></Icon>
