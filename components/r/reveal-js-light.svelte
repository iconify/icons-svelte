<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk87_smea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mk87_smea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reveal-js-light" {...props}></Icon>
