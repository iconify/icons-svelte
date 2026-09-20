<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crho0cbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crho0cbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:raddit-alien-alt" {...props}></Icon>
