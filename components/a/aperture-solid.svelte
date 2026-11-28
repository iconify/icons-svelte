<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odzk71pzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odzk71pzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:aperture-solid" {...props}></Icon>
