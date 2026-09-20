<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya8_7lb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ya8_7lb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-angular-top-right" {...props}></Icon>
