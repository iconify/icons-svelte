<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2e_s8ywe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2e_s8ywe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dev-to" {...props}></Icon>
