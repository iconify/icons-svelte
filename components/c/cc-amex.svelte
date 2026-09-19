<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iagb11b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="iagb11b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cc-amex" {...props}></Icon>
