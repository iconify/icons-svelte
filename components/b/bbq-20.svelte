<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7x7egb-c.css';
import '../../css/s/sqs8isb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c7x7egb-c"/><path class="sqs8isb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bbq-20" {...props}></Icon>
