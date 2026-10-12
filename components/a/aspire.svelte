<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwnhtl0tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwnhtl0tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aspire" {...props}></Icon>
