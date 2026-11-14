<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj6hz_b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj6hz_b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cronos-cro" {...props}></Icon>
