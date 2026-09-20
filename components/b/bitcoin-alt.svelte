<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slhxdacyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slhxdacyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:bitcoin-alt" {...props}></Icon>
