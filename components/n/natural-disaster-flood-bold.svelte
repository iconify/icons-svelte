<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g32-skbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g32-skbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:natural-disaster-flood-bold" {...props}></Icon>
