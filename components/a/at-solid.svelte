<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krths5bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krths5bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:at-solid" {...props}></Icon>
