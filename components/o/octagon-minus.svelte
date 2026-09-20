<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k74guob0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k74guob0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-minus" {...props}></Icon>
