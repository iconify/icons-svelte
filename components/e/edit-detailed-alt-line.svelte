<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4ylnjbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ylnjbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:edit-detailed-alt-line" {...props}></Icon>
