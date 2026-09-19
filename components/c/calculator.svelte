<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqklwyboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqklwyboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calculator" {...props}></Icon>
