<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjf7a61ga.css';
import '../../css/n/n-mc4deaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjf7a61ga"/><path class="n-mc4deaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aviato-dark" {...props}></Icon>
