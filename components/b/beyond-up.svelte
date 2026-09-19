<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd33v-dgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd33v-dgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:beyond-up" {...props}></Icon>
