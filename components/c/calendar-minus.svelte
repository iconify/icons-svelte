<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7u3bta8y.css';
import '../../css/n/nf_ef62wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7u3bta8y"/><path class="nf_ef62wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-minus" {...props}></Icon>
