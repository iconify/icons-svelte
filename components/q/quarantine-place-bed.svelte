<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzf-e_gbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzf-e_gbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:quarantine-place-bed" {...props}></Icon>
