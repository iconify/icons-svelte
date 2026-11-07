<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/e/epahso09d.css';
import '../../css/g/g2-dgp5yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="epahso09d"/><path class="g2-dgp5yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:info-square-bold-duotone" {...props}></Icon>
