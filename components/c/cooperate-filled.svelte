<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md2z_6kln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md2z_6kln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cooperate-filled" {...props}></Icon>
