<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7f46ac0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7f46ac0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cloud-loading-bold" {...props}></Icon>
