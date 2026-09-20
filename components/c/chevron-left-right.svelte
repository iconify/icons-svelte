<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_dy9_tpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_dy9_tpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-left-right" {...props}></Icon>
