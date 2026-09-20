<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_6rk7bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_6rk7bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-right-fill" {...props}></Icon>
