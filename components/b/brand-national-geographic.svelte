<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmzjdnbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmzjdnbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-national-geographic" {...props}></Icon>
