<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_sw5d0mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_sw5d0mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:open-access-logo-block" {...props}></Icon>
