<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma7pcqbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ma7pcqbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:inbox-solid" {...props}></Icon>
