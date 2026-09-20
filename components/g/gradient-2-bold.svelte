<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opd2cccpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="opd2cccpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gradient-2-bold" {...props}></Icon>
