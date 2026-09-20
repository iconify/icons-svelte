<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk43tvbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk43tvbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-plus-filled" {...props}></Icon>
