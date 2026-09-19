<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax7zwolhm.css';
import '../../css/a/ant9fwtwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax7zwolhm"/><path class="ant9fwtwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:big-data-outlined" {...props}></Icon>
