<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh_af3ezb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh_af3ezb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:quarantine-place-hospital" {...props}></Icon>
