<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_dm36b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_dm36b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:radio-filled" {...props}></Icon>
