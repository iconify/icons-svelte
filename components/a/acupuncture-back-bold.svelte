<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkdsworvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkdsworvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:acupuncture-back-bold" {...props}></Icon>
