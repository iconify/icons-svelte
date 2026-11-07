<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epahso09d.css';
import '../../css/g/g2-dgp5yi.css';
import '../../css/f/fhxzx1b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epahso09d"/><path class="g2-dgp5yi"/><path clip-rule="evenodd" class="fhxzx1b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:info-circle-outline" {...props}></Icon>
