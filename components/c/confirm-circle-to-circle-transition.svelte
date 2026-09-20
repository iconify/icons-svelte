<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/q/q9aucu.css';
import '../../css/n/nfmr0h.css';
import '../../css/s/so-to-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c q9aucu"/><path class="a0m25c nfmr0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:confirm-circle-to-circle-transition" {...props}></Icon>
